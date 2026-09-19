<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt9eulz_o.css';
import '../../css/o/o0m5y054f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt9eulz_o"/><path class="o0m5y054f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:donut" {...props}></Icon>
