<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa-q0hbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aa-q0hbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-angry" {...props}></Icon>
