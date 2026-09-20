<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6491dbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6491dbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:divi" {...props}></Icon>
