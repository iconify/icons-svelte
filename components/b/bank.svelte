<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/yh9vutbpe.css';
import '../../css/r/r4h8hkbqs.css';
import '../../css/u/u2qvwgb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="yh9vutbpe"/><path class="r4h8hkbqs"/><path class="u2qvwgb3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bank" {...props}></Icon>
