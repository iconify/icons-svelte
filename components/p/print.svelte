<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0r5uinwc.css';
import '../../css/u/u1-hezbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0r5uinwc"/><path class="u1-hezbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:print" {...props}></Icon>
