<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdokiyzji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qdokiyzji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:comments" {...props}></Icon>
