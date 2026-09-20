<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr0yhbb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr0yhbb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bookmark-slash-24" {...props}></Icon>
