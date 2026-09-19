<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el_f30bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="el_f30bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:panties" {...props}></Icon>
