<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zplly2b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zplly2b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:briefcase-clock" {...props}></Icon>
