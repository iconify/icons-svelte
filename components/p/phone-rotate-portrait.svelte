<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oky9phvzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oky9phvzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-rotate-portrait" {...props}></Icon>
