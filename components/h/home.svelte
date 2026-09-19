<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrav_bckm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrav_bckm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:home" {...props}></Icon>
