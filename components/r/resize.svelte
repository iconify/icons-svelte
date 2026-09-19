<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzny-wb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zzny-wb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:resize" {...props}></Icon>
