<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsigxdbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rsigxdbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:line-arrow-expand-remix" {...props}></Icon>
