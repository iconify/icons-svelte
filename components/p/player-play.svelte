<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acuv0nkdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acuv0nkdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:player-play" {...props}></Icon>
