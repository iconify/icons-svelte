<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oviyegb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":332,"height":512};
const content = `<path class="oviyegb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:cloudsmith" {...props}></Icon>
