<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq6hxe9kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq6hxe9kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:keenetic" {...props}></Icon>
