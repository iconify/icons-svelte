<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/istk6nbhj.css';
import '../../css/q/qqyh0cb9q.css';
import '../../css/e/eumle_byd.css';
import '../../css/z/z0l13u7rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="istk6nbhj"/><path class="qqyh0cb9q wm-a"/><path class="eumle_byd wm-a"/><path class="z0l13u7rz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:apple-duo" {...props}></Icon>
