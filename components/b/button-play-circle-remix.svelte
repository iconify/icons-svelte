<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjwt4m9cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sjwt4m9cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:button-play-circle-remix" {...props}></Icon>
