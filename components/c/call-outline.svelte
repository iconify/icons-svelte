<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foxw_5bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="foxw_5bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:call-outline" {...props}></Icon>
