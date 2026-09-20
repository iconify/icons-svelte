<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw9rg7b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iw9rg7b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:obtainium-dark" {...props}></Icon>
