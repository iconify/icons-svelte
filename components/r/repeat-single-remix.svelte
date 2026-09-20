<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvoikd50e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pvoikd50e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:repeat-single-remix" {...props}></Icon>
