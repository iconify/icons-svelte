<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfajulefx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfajulefx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:doube-window-b-open" {...props}></Icon>
