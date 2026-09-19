<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzui4_y6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="pzui4_y6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:phonebook" {...props}></Icon>
