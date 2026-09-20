<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qngb-pbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qngb-pbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hand-heart-line" {...props}></Icon>
