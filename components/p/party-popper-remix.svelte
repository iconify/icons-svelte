<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2rt8rbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z2rt8rbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:party-popper-remix" {...props}></Icon>
