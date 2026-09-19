<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxa4bxbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bxa4bxbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:clubs" {...props}></Icon>
