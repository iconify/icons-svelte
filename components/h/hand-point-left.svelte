<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1c1yib-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="m1c1yib-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:hand-point-left" {...props}></Icon>
