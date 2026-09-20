<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx6kp1g_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zx6kp1g_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:church-outline" {...props}></Icon>
