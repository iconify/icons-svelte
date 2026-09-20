<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nolqeibdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nolqeibdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dropper-fill" {...props}></Icon>
