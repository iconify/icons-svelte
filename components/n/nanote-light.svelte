<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhoc_olee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dhoc_olee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nanote-light" {...props}></Icon>
