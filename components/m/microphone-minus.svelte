<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6jd7jakm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6jd7jakm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microphone-minus" {...props}></Icon>
