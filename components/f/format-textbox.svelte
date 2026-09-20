<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvyhobc4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvyhobc4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-textbox" {...props}></Icon>
