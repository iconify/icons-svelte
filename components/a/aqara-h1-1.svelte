<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7_yckbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7_yckbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-h1-1" {...props}></Icon>
