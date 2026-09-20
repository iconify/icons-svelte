<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omu4_-bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omu4_-bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:blood-plus-outline" {...props}></Icon>
