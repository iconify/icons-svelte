<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/std8ps_jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="std8ps_jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-up-2-filled" {...props}></Icon>
