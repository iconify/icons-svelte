<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg8vo_0ux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jg8vo_0ux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cat-sitting-and-question-mark" {...props}></Icon>
