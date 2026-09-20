<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy3vwn_zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy3vwn_zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:help-circle" {...props}></Icon>
