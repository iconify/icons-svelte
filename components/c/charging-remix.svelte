<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmyi_m26e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jmyi_m26e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:charging-remix" {...props}></Icon>
