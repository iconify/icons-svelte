<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3vqlzh5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3vqlzh5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:handshake" {...props}></Icon>
