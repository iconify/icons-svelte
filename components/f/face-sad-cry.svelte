<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul1s29bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ul1s29bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-sad-cry" {...props}></Icon>
