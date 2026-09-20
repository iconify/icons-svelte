<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxe-m3zen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xxe-m3zen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:drop-down-menu-remix" {...props}></Icon>
