<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muf9lpbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="muf9lpbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-site-alt2" {...props}></Icon>
