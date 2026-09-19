<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_-9w5b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j_-9w5b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:lock-open-20-solid" {...props}></Icon>
