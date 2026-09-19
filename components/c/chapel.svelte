<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqlazgboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pqlazgboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:chapel" {...props}></Icon>
