<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs2gp9asi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qs2gp9asi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bluesky" {...props}></Icon>
