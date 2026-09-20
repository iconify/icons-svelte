<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1_08bcdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q1_08bcdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:intellectual-remix" {...props}></Icon>
