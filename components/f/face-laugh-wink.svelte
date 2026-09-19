<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd61tvcae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yd61tvcae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:face-laugh-wink" {...props}></Icon>
