<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7g2p8hrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="p7g2p8hrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:play-circle-f" {...props}></Icon>
