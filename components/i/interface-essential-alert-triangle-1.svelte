<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azzl-tb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="azzl-tb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-alert-triangle-1" {...props}></Icon>
