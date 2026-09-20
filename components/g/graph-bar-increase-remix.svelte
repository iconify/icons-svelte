<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt8tarx-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qt8tarx-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:graph-bar-increase-remix" {...props}></Icon>
