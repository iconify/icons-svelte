<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6g6i-iye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y6g6i-iye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:presentation-remix" {...props}></Icon>
