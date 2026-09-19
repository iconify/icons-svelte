<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn73hlbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fn73hlbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:e" {...props}></Icon>
