<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plls9j28h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="plls9j28h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:electric-cord-3-remix" {...props}></Icon>
