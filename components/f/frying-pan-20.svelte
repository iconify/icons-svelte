<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7e500buh.css';
import '../../css/g/gk7nwhbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o7e500buh"/><path class="gk7nwhbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frying-pan-20" {...props}></Icon>
