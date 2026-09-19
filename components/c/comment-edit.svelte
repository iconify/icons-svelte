<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hophqoejb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="hophqoejb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:comment-edit" {...props}></Icon>
