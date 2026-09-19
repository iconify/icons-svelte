<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4gccubns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="q4gccubns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:clock" {...props}></Icon>
