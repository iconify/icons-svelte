<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm43_h9lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="bm43_h9lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:impresscms" {...props}></Icon>
