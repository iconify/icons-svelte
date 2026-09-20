<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmcxs6-ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="rmcxs6-ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:compass-north-west" {...props}></Icon>
