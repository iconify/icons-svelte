<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjafvc-tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zjafvc-tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hydrus-web-dark" {...props}></Icon>
