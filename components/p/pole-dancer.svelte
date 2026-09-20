<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4ozl8-4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q4ozl8-4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:pole-dancer" {...props}></Icon>
