<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h93190bvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="h93190bvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:futbol" {...props}></Icon>
