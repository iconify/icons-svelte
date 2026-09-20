<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbd4s_mlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbd4s_mlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:layout-align-top" {...props}></Icon>
