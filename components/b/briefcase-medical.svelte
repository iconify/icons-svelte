<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clx1tcc9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="clx1tcc9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:briefcase-medical" {...props}></Icon>
