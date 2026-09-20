<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-4sl_2no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l-4sl_2no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:add-1-solid" {...props}></Icon>
