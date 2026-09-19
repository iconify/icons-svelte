<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijuo7pu9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ijuo7pu9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:magic-wand-sparkles" {...props}></Icon>
