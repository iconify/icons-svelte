<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqc_yq4_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lqc_yq4_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:not-available" {...props}></Icon>
