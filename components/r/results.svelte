<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asnmq375y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="asnmq375y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:results" {...props}></Icon>
