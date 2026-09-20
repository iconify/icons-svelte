<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyqr6ubaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyqr6ubaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:move-to-top-24" {...props}></Icon>
