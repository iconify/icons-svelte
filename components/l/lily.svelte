<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alfo9tbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="alfo9tbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lily" {...props}></Icon>
