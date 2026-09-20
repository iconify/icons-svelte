<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0g_tgh1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x0g_tgh1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pacman-solid" {...props}></Icon>
