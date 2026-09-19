<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaj4-5b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uaj4-5b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-minus-16-solid" {...props}></Icon>
