<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iff0e9biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":687,"height":717};
const content = `<path class="iff0e9biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:horizontal" {...props}></Icon>
