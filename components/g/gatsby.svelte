<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulra56alq.css';
import '../../css/s/s3yqb5bmb.css';
import '../../css/q/qtquy_brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="ulra56alq"><path class="s3yqb5bmb"/><path class="qtquy_brk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:gatsby" {...props}></Icon>
