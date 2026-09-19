<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3mrqjpwv.css';
import '../../css/y/yft_2jb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="i3mrqjpwv"/><path class="yft_2jb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:copy-filled" {...props}></Icon>
