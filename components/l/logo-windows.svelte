<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2ogq0u7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f2ogq0u7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-windows" {...props}></Icon>
