<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx2m1lh8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="kx2m1lh8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:ring" {...props}></Icon>
