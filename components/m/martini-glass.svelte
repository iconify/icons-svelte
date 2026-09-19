<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab10wbczk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ab10wbczk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:martini-glass" {...props}></Icon>
