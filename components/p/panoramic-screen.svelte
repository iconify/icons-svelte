<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evc-ukbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="evc-ukbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:panoramic-screen" {...props}></Icon>
