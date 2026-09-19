<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whc-d3s-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="whc-d3s-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cashregister" {...props}></Icon>
