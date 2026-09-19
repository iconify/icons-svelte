<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnje3hq9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnje3hq9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-pause-light" {...props}></Icon>
