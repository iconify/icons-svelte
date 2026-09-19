<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epjxbj1wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="epjxbj1wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-shift-small-filled" {...props}></Icon>
