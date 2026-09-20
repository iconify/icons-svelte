<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyly-ob3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="eyly-ob3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:restaurant-noodle-11" {...props}></Icon>
