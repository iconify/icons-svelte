<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv2g0pfea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv2g0pfea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:accusoft" {...props}></Icon>
