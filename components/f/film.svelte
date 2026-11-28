<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdi_3fcru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdi_3fcru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:film" {...props}></Icon>
