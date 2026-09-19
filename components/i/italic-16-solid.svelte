<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js8pr3blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="js8pr3blz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:italic-16-solid" {...props}></Icon>
