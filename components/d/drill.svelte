<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7sby1g1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d7sby1g1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:drill" {...props}></Icon>
