<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwsj0l8xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gwsj0l8xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:graph-dot-remix" {...props}></Icon>
