<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cds5php0e.css';
import '../../css/w/w2rqhou5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cds5php0e"/><path class="w2rqhou5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:disconnector-20" {...props}></Icon>
