<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-nu6kbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v-nu6kbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-jumping-in-puddle-with-splashes" {...props}></Icon>
