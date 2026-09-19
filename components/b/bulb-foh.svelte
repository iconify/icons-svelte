<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvlve_bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvlve_bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-foh" {...props}></Icon>
