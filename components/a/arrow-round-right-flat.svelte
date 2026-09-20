<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szu8u-bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="szu8u-bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-round-right-flat" {...props}></Icon>
