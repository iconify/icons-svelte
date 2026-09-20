<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syrocm9wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="syrocm9wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flip-vertical-circle-1-solid" {...props}></Icon>
