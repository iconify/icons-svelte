<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqugpjbox.css';
import '../../css/g/g8h-pj3bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mqugpjbox"/><path class="g8h-pj3bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:data-protection" {...props}></Icon>
