<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3-oi6oyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="c3-oi6oyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:restaurant-pizza-11" {...props}></Icon>
