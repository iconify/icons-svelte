<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu-x9zbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="bu-x9zbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:medium" {...props}></Icon>
