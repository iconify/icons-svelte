<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8plw6brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e8plw6brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-bend-left-down-2-solid" {...props}></Icon>
