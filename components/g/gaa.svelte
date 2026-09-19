<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hul69bcrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hul69bcrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:gaa" {...props}></Icon>
