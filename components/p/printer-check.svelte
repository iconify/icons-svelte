<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2hwmtq1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2hwmtq1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:printer-check" {...props}></Icon>
