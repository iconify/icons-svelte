<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccnu6m9vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ccnu6m9vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dna-solid" {...props}></Icon>
