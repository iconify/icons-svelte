<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vheuz5bgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vheuz5bgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:layout-panel-left" {...props}></Icon>
