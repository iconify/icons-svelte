<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm1x6fvcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vm1x6fvcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flip-vertical-square-2-solid" {...props}></Icon>
