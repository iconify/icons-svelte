<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4hn6uk9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="j4hn6uk9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:codeigniter" {...props}></Icon>
