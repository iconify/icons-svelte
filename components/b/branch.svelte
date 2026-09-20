<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh9q0kbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sh9q0kbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:branch" {...props}></Icon>
