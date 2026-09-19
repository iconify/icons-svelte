<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv3re6wbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv3re6wbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:google-home-icon" {...props}></Icon>
