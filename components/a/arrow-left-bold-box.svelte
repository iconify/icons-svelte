<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef296zfzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef296zfzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-left-bold-box" {...props}></Icon>
