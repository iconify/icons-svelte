<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwe_2a0ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwe_2a0ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:body-scan-line" {...props}></Icon>
