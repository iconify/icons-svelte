<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2pee6b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y2pee6b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:phone" {...props}></Icon>
