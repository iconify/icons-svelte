<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxc4urb0d.css';
import '../../css/g/gks8du_si.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxc4urb0d"/><path class="gks8du_si"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:check-box" {...props}></Icon>
