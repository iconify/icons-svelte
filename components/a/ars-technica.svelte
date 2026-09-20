<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3fm6ybam.css';
import '../../css/t/tegirhu2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="f3fm6ybam"/><path class="tegirhu2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ars-technica" {...props}></Icon>
