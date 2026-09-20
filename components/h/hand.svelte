<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7m834b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="w7m834b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:hand" {...props}></Icon>
