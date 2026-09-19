<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjm4uds7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rjm4uds7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:purse" {...props}></Icon>
