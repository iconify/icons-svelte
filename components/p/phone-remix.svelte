<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whlbo9qbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="whlbo9qbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:phone-remix" {...props}></Icon>
