<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/son0shbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="son0shbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bluetooth-off" {...props}></Icon>
