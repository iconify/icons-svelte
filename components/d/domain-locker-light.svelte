<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_20abpwf.css';
import '../../css/m/m01ydll8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n_20abpwf"/><path class="m01ydll8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:domain-locker-light" {...props}></Icon>
