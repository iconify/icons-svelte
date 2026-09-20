<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmwp9acui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dmwp9acui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-question-mark" {...props}></Icon>
