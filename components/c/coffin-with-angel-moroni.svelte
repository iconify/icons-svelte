<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_87cvbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l_87cvbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffin-with-angel-moroni" {...props}></Icon>
