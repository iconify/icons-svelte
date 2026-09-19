<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5d58pb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e5d58pb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:person-voice" {...props}></Icon>
