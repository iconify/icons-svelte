<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i68o4rb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i68o4rb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:comment-alt" {...props}></Icon>
