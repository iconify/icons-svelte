<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdr0_jbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdr0_jbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:earth-3-line" {...props}></Icon>
