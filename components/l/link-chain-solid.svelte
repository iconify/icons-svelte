<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3a7ce9nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d3a7ce9nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:link-chain-solid" {...props}></Icon>
