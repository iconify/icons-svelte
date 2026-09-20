<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yen6d0buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yen6d0buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-list-numbered" {...props}></Icon>
