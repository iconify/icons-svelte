<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebn0rgpcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ebn0rgpcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:omada" {...props}></Icon>
