<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0mg5_20h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z0mg5_20h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:fork-knife-remix" {...props}></Icon>
