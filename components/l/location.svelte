<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x692j4b5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x692j4b5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:location" {...props}></Icon>
