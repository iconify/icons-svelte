<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le12s8byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="le12s8byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:golf-club-and-ball" {...props}></Icon>
