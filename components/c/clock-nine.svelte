<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_0eu_baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_0eu_baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:clock-nine" {...props}></Icon>
