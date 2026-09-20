<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s43rqw6eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s43rqw6eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:crumpled-paper" {...props}></Icon>
