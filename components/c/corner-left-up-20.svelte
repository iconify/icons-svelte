<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whsuzhbnb.css';
import '../../css/d/d8lq7obnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="whsuzhbnb"/><path class="d8lq7obnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-left-up-20" {...props}></Icon>
