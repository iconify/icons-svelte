<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/ktq1g1b0a.css';
import '../../css/a/ajv3mbcxk.css';
import '../../css/y/yv6bixhwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ktq1g1b0a"/><path class="ajv3mbcxk"/><path class="yv6bixhwc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:battery-low" {...props}></Icon>
