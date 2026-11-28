<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9-2w9czx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9-2w9czx primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:move-duotone" {...props}></Icon>
