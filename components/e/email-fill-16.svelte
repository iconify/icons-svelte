<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1tg5un7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x1tg5un7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:email-fill-16" {...props}></Icon>
