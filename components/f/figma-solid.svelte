<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e72c6_bdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e72c6_bdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:figma-solid" {...props}></Icon>
