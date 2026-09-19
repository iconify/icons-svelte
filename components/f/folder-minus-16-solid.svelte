<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elgdx1llj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="elgdx1llj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:folder-minus-16-solid" {...props}></Icon>
