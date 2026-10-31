<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uakihh5sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uakihh5sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-u-turn-down-left-bulk-round" {...props}></Icon>
