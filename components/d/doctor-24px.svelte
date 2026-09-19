<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twbw68b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twbw68b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:doctor-24px" {...props}></Icon>
