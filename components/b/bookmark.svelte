<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dee6m-bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dee6m-bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:bookmark" {...props}></Icon>
