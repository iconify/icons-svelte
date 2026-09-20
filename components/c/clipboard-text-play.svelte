<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo4ugdb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wo4ugdb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-text-play" {...props}></Icon>
