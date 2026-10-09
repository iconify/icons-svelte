<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi_kil9dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mi_kil9dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-rating-48" {...props}></Icon>
