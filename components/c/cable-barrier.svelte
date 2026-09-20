<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc3oh_kgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wc3oh_kgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:cable-barrier" {...props}></Icon>
