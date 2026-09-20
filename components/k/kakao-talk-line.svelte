<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdd12bcok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdd12bcok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:kakao-talk-line" {...props}></Icon>
