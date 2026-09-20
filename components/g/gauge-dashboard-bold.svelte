<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-h3xgbno.css';
import '../../css/k/k-2dhebbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-h3xgbno"/><path class="k-2dhebbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:gauge-dashboard-bold" {...props}></Icon>
