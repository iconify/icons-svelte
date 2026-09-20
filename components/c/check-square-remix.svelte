<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iure-wb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iure-wb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:check-square-remix" {...props}></Icon>
