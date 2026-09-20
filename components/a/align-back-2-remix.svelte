<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc6ecmbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pc6ecmbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:align-back-2-remix" {...props}></Icon>
