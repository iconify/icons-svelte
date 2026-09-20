<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd2dswubh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vd2dswubh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:bolt" {...props}></Icon>
