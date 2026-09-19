<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl3q62b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fl3q62b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:pager" {...props}></Icon>
