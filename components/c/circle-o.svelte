<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3iju5bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="e3iju5bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:circle-o" {...props}></Icon>
