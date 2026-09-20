<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyyvpzxdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uyyvpzxdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mantrae-light" {...props}></Icon>
