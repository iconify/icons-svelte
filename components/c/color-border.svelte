<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_zl739_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_zl739_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:color-border" {...props}></Icon>
