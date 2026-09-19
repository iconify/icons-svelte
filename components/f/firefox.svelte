<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_372t7wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="t_372t7wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:firefox" {...props}></Icon>
