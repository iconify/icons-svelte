<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg4wpe13k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg4wpe13k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:compress-point" {...props}></Icon>
