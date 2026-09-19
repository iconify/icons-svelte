<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_c9fob0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1024};
const content = `<path class="w_c9fob0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mahara" {...props}></Icon>
