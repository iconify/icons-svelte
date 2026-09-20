<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn3czrb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rn3czrb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:restaurant-bbq" {...props}></Icon>
