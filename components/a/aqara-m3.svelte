<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug9i3c-fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug9i3c-fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-m3" {...props}></Icon>
