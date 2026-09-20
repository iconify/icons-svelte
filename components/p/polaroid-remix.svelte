<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb0re9w3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mb0re9w3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:polaroid-remix" {...props}></Icon>
