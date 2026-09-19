<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l562sp3ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l562sp3ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:comment-discussion-quote" {...props}></Icon>
