<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c59wd2bpx.css';
import '../../css/m/m6cog7b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c59wd2bpx"/><path class="m6cog7b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bottle-line" {...props}></Icon>
