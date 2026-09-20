<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc-4ceb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tc-4ceb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:camera-disabled-remix" {...props}></Icon>
