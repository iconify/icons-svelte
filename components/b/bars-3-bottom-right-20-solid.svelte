<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rok2wacqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rok2wacqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-3-bottom-right-20-solid" {...props}></Icon>
