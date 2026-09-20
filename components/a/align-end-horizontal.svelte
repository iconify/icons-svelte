<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdv1--bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdv1--bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-end-horizontal" {...props}></Icon>
