<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zssuzstjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zssuzstjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:history-fill-12" {...props}></Icon>
