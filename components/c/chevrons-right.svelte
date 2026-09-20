<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqgnghnpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqgnghnpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chevrons-right" {...props}></Icon>
