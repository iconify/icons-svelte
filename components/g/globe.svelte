<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvhof_brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rvhof_brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:globe" {...props}></Icon>
