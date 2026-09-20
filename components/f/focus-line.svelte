<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqgz50euy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqgz50euy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:focus-line" {...props}></Icon>
