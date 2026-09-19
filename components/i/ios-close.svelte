<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4igrcb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s4igrcb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-close" {...props}></Icon>
