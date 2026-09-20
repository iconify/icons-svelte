<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk63d0d6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="pk63d0d6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:plus-circle" {...props}></Icon>
