<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w19dqybpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="w19dqybpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:litecoin-solid" {...props}></Icon>
