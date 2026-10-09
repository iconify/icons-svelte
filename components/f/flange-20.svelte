<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4bjo-bjt.css';
import '../../css/v/v4ji3vb6c.css';
import '../../css/g/gqvbnmbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r4bjo-bjt"/><path class="v4ji3vb6c"/><path class="gqvbnmbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flange-20" {...props}></Icon>
