<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e29uutbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="e29uutbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:circle" {...props}></Icon>
