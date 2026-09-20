<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq4enbcmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jq4enbcmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-align-bottom" {...props}></Icon>
