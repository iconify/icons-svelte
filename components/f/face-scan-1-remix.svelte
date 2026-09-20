<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm36d0bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lm36d0bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:face-scan-1-remix" {...props}></Icon>
