<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cog2mfnwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cog2mfnwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:list-alt" {...props}></Icon>
