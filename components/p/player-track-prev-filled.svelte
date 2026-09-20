<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_lf64b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_lf64b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:player-track-prev-filled" {...props}></Icon>
