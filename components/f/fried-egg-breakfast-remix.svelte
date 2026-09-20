<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdt75mt-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kdt75mt-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:fried-egg-breakfast-remix" {...props}></Icon>
