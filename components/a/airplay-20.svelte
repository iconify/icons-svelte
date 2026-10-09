<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve2d5cbgv.css';
import '../../css/a/ay_ybxb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ve2d5cbgv"/><path class="ay_ybxb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:airplay-20" {...props}></Icon>
