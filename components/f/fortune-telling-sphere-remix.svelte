<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j416pfu1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j416pfu1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:fortune-telling-sphere-remix" {...props}></Icon>
