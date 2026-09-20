<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnvgpw3_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnvgpw3_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:notes" {...props}></Icon>
