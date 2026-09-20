<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d93dmed3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d93dmed3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:arrow-cursor-1-remix" {...props}></Icon>
