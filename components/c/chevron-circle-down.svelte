<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if6e8ibdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="if6e8ibdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:chevron-circle-down" {...props}></Icon>
