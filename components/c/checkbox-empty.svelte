<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llf2_5bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="llf2_5bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:checkbox-empty" {...props}></Icon>
