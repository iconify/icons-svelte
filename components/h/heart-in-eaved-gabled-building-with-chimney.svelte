<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq-rkobcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bq-rkobcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:heart-in-eaved-gabled-building-with-chimney" {...props}></Icon>
