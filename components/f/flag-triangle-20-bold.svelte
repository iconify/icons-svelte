<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-ahsnbld.css';
import '../../css/b/b8tuyrvbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h-ahsnbld"/><path class="b8tuyrvbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flag-triangle-20-bold" {...props}></Icon>
