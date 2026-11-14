<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/a/a0e-esbbh.css';
import '../../css/g/g0lkk6boj.css';
import '../../css/g/g1tth5biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a0e-esbbh"/><path class="g0lkk6boj"/><path class="g1tth5biz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-preview-01" {...props}></Icon>
