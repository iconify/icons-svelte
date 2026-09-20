<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxn07f95d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxn07f95d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:question-network-outline" {...props}></Icon>
