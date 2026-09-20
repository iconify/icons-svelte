<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auhlrw2_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="auhlrw2_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:circle-3" {...props}></Icon>
