<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_t-l-btv.css';
import '../../css/h/h6g7afq-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_t-l-btv"/><path class="h6g7afq-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pie-chart-3-bold" {...props}></Icon>
