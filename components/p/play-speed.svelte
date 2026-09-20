<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpqy10b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpqy10b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:play-speed" {...props}></Icon>
