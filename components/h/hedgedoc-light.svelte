<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7m6rhbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b7m6rhbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hedgedoc-light" {...props}></Icon>
