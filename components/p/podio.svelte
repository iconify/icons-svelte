<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9_xqi7vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l9_xqi7vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:podio" {...props}></Icon>
