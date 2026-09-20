<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaiqco-dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gaiqco-dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:chat-bubble-text-square-solid" {...props}></Icon>
