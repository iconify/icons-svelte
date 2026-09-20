<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyzc91b1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jyzc91b1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:line-arrow-triangle-loop-remix" {...props}></Icon>
