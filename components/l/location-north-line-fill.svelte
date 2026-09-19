<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt0e-l7es.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lt0e-l7es"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:location-north-line-fill" {...props}></Icon>
