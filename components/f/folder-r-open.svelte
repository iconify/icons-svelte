<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh0zkx8bv.css';
import '../../css/y/yud54w-4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jh0zkx8bv"/><path class="yud54w-4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-r-open" {...props}></Icon>
