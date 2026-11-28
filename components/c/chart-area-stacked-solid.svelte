<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upp0l4w6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upp0l4w6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chart-area-stacked-solid" {...props}></Icon>
