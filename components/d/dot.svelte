<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za30a2l0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="za30a2l0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:dot" {...props}></Icon>
