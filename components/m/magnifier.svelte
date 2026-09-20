<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy8doab7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hy8doab7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:magnifier" {...props}></Icon>
