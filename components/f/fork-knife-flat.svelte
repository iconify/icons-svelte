<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf9aldbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gf9aldbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:fork-knife-flat" {...props}></Icon>
