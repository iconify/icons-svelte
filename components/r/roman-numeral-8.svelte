<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmjhv4bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmjhv4bre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:roman-numeral-8" {...props}></Icon>
