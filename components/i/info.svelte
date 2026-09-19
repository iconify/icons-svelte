<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt9-lrb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wt9-lrb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:info" {...props}></Icon>
