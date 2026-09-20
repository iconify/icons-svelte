<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iskvlvbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iskvlvbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bed-and-roof" {...props}></Icon>
