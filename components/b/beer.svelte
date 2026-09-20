<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu9s651lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bu9s651lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:beer" {...props}></Icon>
