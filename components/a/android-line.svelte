<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4ops_xbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4ops_xbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:android-line" {...props}></Icon>
