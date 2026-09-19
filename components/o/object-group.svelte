<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b48lj4b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1792};
const content = `<path class="b48lj4b-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:object-group" {...props}></Icon>
