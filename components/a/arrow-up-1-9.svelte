<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svdqlfoiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="svdqlfoiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-up-1-9" {...props}></Icon>
