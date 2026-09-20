<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw0c2llzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bw0c2llzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:alcohol-shop-15" {...props}></Icon>
