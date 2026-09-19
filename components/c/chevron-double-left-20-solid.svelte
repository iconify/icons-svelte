<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylq9gqi5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ylq9gqi5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-double-left-20-solid" {...props}></Icon>
