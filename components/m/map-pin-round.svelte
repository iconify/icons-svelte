<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykrfa-b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykrfa-b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:map-pin-round" {...props}></Icon>
