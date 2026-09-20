<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0_rvbb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0_rvbb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:file-code-bold" {...props}></Icon>
