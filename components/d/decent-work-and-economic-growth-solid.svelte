<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j09701bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j09701bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:decent-work-and-economic-growth-solid" {...props}></Icon>
