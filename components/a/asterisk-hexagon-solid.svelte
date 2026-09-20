<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muej_p33h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muej_p33h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:asterisk-hexagon-solid" {...props}></Icon>
