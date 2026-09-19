<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf8jptdul.css';
import '../../css/o/o1y82wb2y.css';
import '../../css/m/mstdj_b5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cf8jptdul"/><path class="o1y82wb2y"/><path class="mstdj_b5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:minidsp" {...props}></Icon>
