<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quwyzac4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="quwyzac4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:library-compact" {...props}></Icon>
