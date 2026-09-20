<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcr_wdbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rcr_wdbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:boombox" {...props}></Icon>
