<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n41l_qsqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n41l_qsqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:ambulance" {...props}></Icon>
