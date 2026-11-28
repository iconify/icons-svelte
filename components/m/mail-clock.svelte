<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp4yiccgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp4yiccgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mail-clock" {...props}></Icon>
