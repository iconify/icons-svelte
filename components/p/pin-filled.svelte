<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bliqavuzu.css';
import '../../css/u/uk1d9ew2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="bliqavuzu"/><path class="uk1d9ew2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pin-filled" {...props}></Icon>
