<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqkdsdbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqkdsdbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:night-club-disco-ball-bold" {...props}></Icon>
