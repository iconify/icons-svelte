<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls5zy66mw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls5zy66mw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:map-pin-heart-round" {...props}></Icon>
