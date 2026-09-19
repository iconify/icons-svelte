<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrh39abmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrh39abmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-air-quality" {...props}></Icon>
