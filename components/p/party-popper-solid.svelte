<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfcj4ebkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rfcj4ebkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:party-popper-solid" {...props}></Icon>
