<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm51bcbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dm51bcbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-3-circle-fill" {...props}></Icon>
