<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw4uepb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw4uepb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:jump-off" {...props}></Icon>
