<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj449perf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj449perf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:eye-off-line" {...props}></Icon>
