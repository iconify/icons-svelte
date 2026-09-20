<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcq_hib2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jcq_hib2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ok-hand-remix" {...props}></Icon>
