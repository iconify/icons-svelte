<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shvnqsbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shvnqsbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-r-circle" {...props}></Icon>
