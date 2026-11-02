<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmieo0byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmieo0byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hight-beam-headlights-fill" {...props}></Icon>
