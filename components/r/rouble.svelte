<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp4ozmbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wp4ozmbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:rouble" {...props}></Icon>
