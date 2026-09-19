<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeos434il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jeos434il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:person-harassing" {...props}></Icon>
