<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snw6p3bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snw6p3bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:black-hole2-filled" {...props}></Icon>
