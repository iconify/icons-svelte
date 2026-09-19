<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d10gvkb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d10gvkb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:building-library-20-solid" {...props}></Icon>
