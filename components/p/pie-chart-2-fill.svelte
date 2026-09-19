<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9srj5bbq.css';
import '../../css/w/w81_4cfys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9srj5bbq"/><path class="w81_4cfys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:pie-chart-2-fill" {...props}></Icon>
