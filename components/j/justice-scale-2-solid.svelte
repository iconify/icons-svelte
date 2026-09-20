<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew5vkeiha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ew5vkeiha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:justice-scale-2-solid" {...props}></Icon>
