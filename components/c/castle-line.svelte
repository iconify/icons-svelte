<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3bj07bek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3bj07bek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:castle-line" {...props}></Icon>
