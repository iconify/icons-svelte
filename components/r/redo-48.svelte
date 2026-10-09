<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooff228am.css';
import '../../css/d/d0qdug7jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ooff228am"/><path class="d0qdug7jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:redo-48" {...props}></Icon>
