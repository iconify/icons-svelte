<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw6ek34qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="iw6ek34qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:crown" {...props}></Icon>
