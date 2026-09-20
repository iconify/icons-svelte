<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzs8krkut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dzs8krkut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:milk-remix" {...props}></Icon>
