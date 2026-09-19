<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojdde1gbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojdde1gbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-hub-n15-g2" {...props}></Icon>
