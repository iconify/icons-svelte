<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr4ffz20i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="kr4ffz20i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:chat" {...props}></Icon>
