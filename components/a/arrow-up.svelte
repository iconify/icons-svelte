<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2uy08i6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="w2uy08i6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-up" {...props}></Icon>
