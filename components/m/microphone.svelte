<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkb_xbcbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkb_xbcbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:microphone" {...props}></Icon>
