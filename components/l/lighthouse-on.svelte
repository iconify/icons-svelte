<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buxoumbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="buxoumbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lighthouse-on" {...props}></Icon>
