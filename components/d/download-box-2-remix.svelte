<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7qmocviu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i7qmocviu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:download-box-2-remix" {...props}></Icon>
