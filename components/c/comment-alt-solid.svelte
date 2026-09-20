<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc1r45b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jc1r45b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:comment-alt-solid" {...props}></Icon>
