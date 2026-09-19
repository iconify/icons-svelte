<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lybe10l9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lybe10l9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:home3" {...props}></Icon>
