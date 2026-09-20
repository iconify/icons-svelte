<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_va5_htj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l_va5_htj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:clean-water-and-sanitation-remix" {...props}></Icon>
