<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msu-j-bsq.css';
import '../../css/j/j4ehiv-dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="msu-j-bsq"/><path class="j4ehiv-dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pen-to-square" {...props}></Icon>
