<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8be29jfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="h8be29jfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:chalkboard-teacher" {...props}></Icon>
