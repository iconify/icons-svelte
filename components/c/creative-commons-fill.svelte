<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npngynb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npngynb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:creative-commons-fill" {...props}></Icon>
