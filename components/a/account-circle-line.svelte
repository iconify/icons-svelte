<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnmvl1dlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnmvl1dlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:account-circle-line" {...props}></Icon>
