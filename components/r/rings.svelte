<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icn631b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="icn631b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:rings" {...props}></Icon>
