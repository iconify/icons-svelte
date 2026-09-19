<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/reyg2abim.css';
import '../../css/j/jsk_qbbtn.css';
import '../../css/k/k6i8m5bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="reyg2abim"/><path class="jsk_qbbtn"/><path class="k6i8m5bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-calendar" {...props}></Icon>
