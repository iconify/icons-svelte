<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyzn85bno.css';
import '../../css/t/tky-zccgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyzn85bno"/><path class="tky-zccgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-thermometer" {...props}></Icon>
