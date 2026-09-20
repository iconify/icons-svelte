<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8yt5dwlu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j8yt5dwlu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:parachute-drop-remix" {...props}></Icon>
