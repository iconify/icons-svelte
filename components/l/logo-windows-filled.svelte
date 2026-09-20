<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6l8-5blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6l8-5blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-windows-filled" {...props}></Icon>
