<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us6b7-d0g.css';
import '../../css/p/p78ussb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="us6b7-d0g"/><path class="p78ussb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:battery-quarter" {...props}></Icon>
