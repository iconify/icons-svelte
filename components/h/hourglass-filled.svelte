<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-7afx7hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-7afx7hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:hourglass-filled" {...props}></Icon>
