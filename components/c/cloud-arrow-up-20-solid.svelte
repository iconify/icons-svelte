<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl5xlyp8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="yl5xlyp8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cloud-arrow-up-20-solid" {...props}></Icon>
