<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgkz-7bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgkz-7bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:activity-filled" {...props}></Icon>
