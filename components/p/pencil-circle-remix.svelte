<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do32_5buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="do32_5buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pencil-circle-remix" {...props}></Icon>
