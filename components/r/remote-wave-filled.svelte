<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9dg3bzxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9dg3bzxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:remote-wave-filled" {...props}></Icon>
