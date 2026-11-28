<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb4_doy5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb4_doy5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:area-chart" {...props}></Icon>
