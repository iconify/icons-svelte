<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of_es-dhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="of_es-dhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:bread-slice" {...props}></Icon>
