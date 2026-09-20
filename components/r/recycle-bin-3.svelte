<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhwy1acak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bhwy1acak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:recycle-bin-3" {...props}></Icon>
