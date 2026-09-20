<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwqbv6b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kwqbv6b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bleachers" {...props}></Icon>
