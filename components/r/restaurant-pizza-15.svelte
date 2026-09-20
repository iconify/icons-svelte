<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqlqe17_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mqlqe17_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:restaurant-pizza-15" {...props}></Icon>
