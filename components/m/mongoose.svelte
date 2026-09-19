<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5nmllbgc.css';
import '../../css/m/m3qb8jb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="t5nmllbgc"/><path class="m3qb8jb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:mongoose" {...props}></Icon>
