<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y74p83nwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="y74p83nwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:chess-king" {...props}></Icon>
