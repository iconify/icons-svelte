<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5amrmbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w5amrmbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:lost-and-found-remix" {...props}></Icon>
