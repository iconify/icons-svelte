<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3aqtzbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t3aqtzbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netlock-rmm-light" {...props}></Icon>
