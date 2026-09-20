<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tedvp2apz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tedvp2apz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:psychology-outline" {...props}></Icon>
