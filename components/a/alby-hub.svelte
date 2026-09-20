<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f40rxmbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f40rxmbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alby-hub" {...props}></Icon>
