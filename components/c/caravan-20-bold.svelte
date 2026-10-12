<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9yynmbhe.css';
import '../../css/g/g-xpidcsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c9yynmbhe"/><path class="g-xpidcsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caravan-20-bold" {...props}></Icon>
