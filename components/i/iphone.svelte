<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o99brqgby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o99brqgby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:iphone" {...props}></Icon>
