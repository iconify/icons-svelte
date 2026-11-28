<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sb-u7hbtr.css';
import '../../css/n/n7nnzhblg.css';
import '../../css/e/e5edqev6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="sb-u7hbtr"/><path class="n7nnzhblg"/><path class="e5edqev6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pager" {...props}></Icon>
