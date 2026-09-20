<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7dqf_b7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":204};
const content = `<path class="y7dqf_b7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bootstrap" {...props}></Icon>
