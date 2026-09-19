<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtnxyp9na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jtnxyp9na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:angular" {...props}></Icon>
