<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3q8gnbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h3q8gnbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:exchange" {...props}></Icon>
