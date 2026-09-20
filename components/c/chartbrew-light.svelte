<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh-xzlbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hh-xzlbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chartbrew-light" {...props}></Icon>
