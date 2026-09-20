<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku3rmihjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ku3rmihjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:airplane-disabled-solid" {...props}></Icon>
