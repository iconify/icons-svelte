<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb4eypbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eb4eypbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:diagnoses" {...props}></Icon>
