<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phqk2vbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="phqk2vbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:atera-light" {...props}></Icon>
