<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkrqb7brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jkrqb7brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:gulp" {...props}></Icon>
