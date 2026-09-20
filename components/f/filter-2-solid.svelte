<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etic5kuwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="etic5kuwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:filter-2-solid" {...props}></Icon>
