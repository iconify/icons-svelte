<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_bfm19uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i_bfm19uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plane-20-bold" {...props}></Icon>
