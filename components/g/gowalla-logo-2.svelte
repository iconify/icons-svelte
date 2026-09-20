<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc_3y57dd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc_3y57dd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:gowalla-logo-2" {...props}></Icon>
