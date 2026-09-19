<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5yn9ndtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z5yn9ndtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:close-outline" {...props}></Icon>
