<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_elmvb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p_elmvb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:grid" {...props}></Icon>
