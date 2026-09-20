<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3kj7i7gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p3kj7i7gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-heavy-six-point-asterisk" {...props}></Icon>
