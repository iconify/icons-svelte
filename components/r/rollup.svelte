<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9ljs0bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":800,"height":800,"left":100,"top":100};
const content = `<path class="z9ljs0bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:rollup" {...props}></Icon>
