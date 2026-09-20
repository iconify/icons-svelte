<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_h9oache.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="b_h9oache"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:circle-11" {...props}></Icon>
