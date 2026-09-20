<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt7qfob9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wt7qfob9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pyramid-shape-remix" {...props}></Icon>
