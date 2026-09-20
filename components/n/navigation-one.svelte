<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm1ax3iyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm1ax3iyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:navigation-one" {...props}></Icon>
