<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b62x9aczy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b62x9aczy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cards-playing-spade-multiple" {...props}></Icon>
