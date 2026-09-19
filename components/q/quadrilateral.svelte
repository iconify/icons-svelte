<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nllsco9uf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nllsco9uf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:quadrilateral" {...props}></Icon>
