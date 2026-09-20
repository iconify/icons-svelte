<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzzs7mk9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rzzs7mk9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:inbox-post-remix" {...props}></Icon>
