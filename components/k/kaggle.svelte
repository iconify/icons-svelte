<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3gqcf4nl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="j3gqcf4nl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:kaggle" {...props}></Icon>
