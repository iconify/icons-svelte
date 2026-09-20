<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww1159bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ww1159bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hierarchy-16-remix" {...props}></Icon>
