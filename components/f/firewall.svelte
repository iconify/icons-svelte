<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzj2zq6ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="gzj2zq6ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:firewall" {...props}></Icon>
