<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpf444bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vpf444bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:battery-empty-1-solid" {...props}></Icon>
