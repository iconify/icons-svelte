<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4up2objj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4up2objj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:expansion-card-variant" {...props}></Icon>
