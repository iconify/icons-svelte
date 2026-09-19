<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj_r53b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="nj_r53b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:brain" {...props}></Icon>
