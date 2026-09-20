<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v95o1pkwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v95o1pkwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:planet-off" {...props}></Icon>
