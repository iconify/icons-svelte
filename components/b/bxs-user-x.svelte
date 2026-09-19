<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s89t19bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s89t19bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-user-x" {...props}></Icon>
