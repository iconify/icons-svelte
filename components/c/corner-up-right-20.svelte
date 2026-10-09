<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6i7h5b1b.css';
import '../../css/a/a98cjoanz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n6i7h5b1b"/><path class="a98cjoanz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-up-right-20" {...props}></Icon>
