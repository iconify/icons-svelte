<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abt6-fbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1280};
const content = `<path class="abt6-fbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:battery-1" {...props}></Icon>
