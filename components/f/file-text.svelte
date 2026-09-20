<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkft-oqzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pkft-oqzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:file-text" {...props}></Icon>
