<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2_xb8b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j2_xb8b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:phone-ringing-1-remix" {...props}></Icon>
