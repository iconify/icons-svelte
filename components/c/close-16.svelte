<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9c8rcbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f9c8rcbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:close-16" {...props}></Icon>
