<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-gja2bhg.css';
import '../../css/v/vnep0m7rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-gja2bhg"/><path class="vnep0m7rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-down-right-circle" {...props}></Icon>
