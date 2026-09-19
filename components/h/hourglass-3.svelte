<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqgw987ga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="kqgw987ga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hourglass-3" {...props}></Icon>
