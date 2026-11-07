<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p91k6tbgq.css';
import '../../css/t/tuxrhtbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p91k6tbgq"/><path clip-rule="evenodd" class="tuxrhtbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-close-outline" {...props}></Icon>
