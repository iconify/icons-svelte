<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz32iacsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pz32iacsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ascending-alphabetical-order" {...props}></Icon>
