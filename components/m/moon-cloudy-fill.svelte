<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzubqt2mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzubqt2mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moon-cloudy-fill" {...props}></Icon>
