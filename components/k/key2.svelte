<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohw1k-bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ohw1k-bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:key2" {...props}></Icon>
