<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_mtb3oij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d_mtb3oij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bill" {...props}></Icon>
