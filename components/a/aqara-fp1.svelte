<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz7do5bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rz7do5bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-fp1" {...props}></Icon>
