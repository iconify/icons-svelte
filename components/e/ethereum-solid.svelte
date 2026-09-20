<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doi97okei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="doi97okei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ethereum-solid" {...props}></Icon>
