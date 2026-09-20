<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmo-e-bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fmo-e-bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:record-player-remix" {...props}></Icon>
