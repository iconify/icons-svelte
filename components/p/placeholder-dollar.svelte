<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbxwgrbol.css';
import '../../css/p/pyk3d0bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="qbxwgrbol"/><path clip-rule="evenodd" class="pyk3d0bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:placeholder-dollar" {...props}></Icon>
