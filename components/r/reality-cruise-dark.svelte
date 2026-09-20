<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkw_0_bqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pkw_0_bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reality-cruise-dark" {...props}></Icon>
