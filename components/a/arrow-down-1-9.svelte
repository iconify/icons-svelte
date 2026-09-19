<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d78vz38qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="d78vz38qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-down-1-9" {...props}></Icon>
