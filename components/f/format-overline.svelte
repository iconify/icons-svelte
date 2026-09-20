<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/objpm4zrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="objpm4zrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-overline" {...props}></Icon>
