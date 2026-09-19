<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw5ybfjdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lw5ybfjdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:partly-sunny-sharp" {...props}></Icon>
