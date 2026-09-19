<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y21dk_wfs.css';
import '../../css/k/k4mqvjn9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y21dk_wfs"/><path class="k4mqvjn9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:change-catalog" {...props}></Icon>
