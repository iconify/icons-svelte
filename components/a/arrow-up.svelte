<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzlz_vbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="hzlz_vbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:arrow-up" {...props}></Icon>
