<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5t-s_b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="l5t-s_b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:invisible-1-remix" {...props}></Icon>
