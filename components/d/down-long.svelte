<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cco7ibccm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cco7ibccm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:down-long" {...props}></Icon>
