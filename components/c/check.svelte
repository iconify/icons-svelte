<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p364vhbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p364vhbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:check" {...props}></Icon>
