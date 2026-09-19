<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1k3llb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d1k3llb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:edge" {...props}></Icon>
