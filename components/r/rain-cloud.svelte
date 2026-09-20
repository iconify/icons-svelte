<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9gy4gb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="q9gy4gb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:rain-cloud" {...props}></Icon>
