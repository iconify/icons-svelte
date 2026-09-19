<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbmw3_k5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cbmw3_k5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:phone-x-mark" {...props}></Icon>
