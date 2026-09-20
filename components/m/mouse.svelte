<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c29q9gyiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="c29q9gyiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:mouse" {...props}></Icon>
