<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0n8qekfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="c0n8qekfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:brightness" {...props}></Icon>
