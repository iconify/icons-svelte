<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi8rshb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi8rshb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-left-filled" {...props}></Icon>
