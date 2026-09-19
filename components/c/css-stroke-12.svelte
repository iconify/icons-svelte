<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-cmxab5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="d-cmxab5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:css-stroke-12" {...props}></Icon>
