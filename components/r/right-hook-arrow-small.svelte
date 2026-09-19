<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1lmu7b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="c1lmu7b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:right-hook-arrow-small" {...props}></Icon>
