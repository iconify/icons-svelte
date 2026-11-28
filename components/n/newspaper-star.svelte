<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnm_kko2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnm_kko2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:newspaper-star" {...props}></Icon>
