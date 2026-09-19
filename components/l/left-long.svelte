<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzugy2bdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mzugy2bdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:left-long" {...props}></Icon>
