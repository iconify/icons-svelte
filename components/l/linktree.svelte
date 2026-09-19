<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnvzf6rtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="hnvzf6rtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:linktree" {...props}></Icon>
