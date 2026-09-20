<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwwnpvb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lwwnpvb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-remove-solid" {...props}></Icon>
