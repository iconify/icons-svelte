<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv5sewmdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nv5sewmdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:like-1-remix" {...props}></Icon>
