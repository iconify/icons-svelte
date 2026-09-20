<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teur4xb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="teur4xb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:galaxy-2-solid" {...props}></Icon>
