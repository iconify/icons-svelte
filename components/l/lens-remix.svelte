<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxdr_ubpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hxdr_ubpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:lens-remix" {...props}></Icon>
