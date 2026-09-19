<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd5r6kjzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gd5r6kjzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:arrow-right" {...props}></Icon>
