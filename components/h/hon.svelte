<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fld9aqiof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fld9aqiof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hon" {...props}></Icon>
