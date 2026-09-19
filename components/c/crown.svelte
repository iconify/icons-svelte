<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj42u0b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zj42u0b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:crown" {...props}></Icon>
