<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkm2a9i0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkm2a9i0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-wide-narrow" {...props}></Icon>
