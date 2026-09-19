<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwqlp4b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wwqlp4b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:42-group" {...props}></Icon>
