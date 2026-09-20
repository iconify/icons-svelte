<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg-1gacwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg-1gacwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:progress-pencil" {...props}></Icon>
