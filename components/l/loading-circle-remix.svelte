<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7sni-u8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y7sni-u8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:loading-circle-remix" {...props}></Icon>
