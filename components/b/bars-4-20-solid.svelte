<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0o66qbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j0o66qbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-4-20-solid" {...props}></Icon>
