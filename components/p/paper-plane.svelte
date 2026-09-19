<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk2lnt3lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jk2lnt3lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:paper-plane" {...props}></Icon>
