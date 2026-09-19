<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhltm17vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhltm17vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-blind-half" {...props}></Icon>
