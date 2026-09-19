<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd180xnta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fd180xnta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:chevron-up" {...props}></Icon>
