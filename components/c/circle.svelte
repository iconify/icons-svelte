<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cacc3j1kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cacc3j1kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:circle" {...props}></Icon>
