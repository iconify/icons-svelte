<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv_oq7_es.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bv_oq7_es"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:app-switch" {...props}></Icon>
