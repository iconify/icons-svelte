<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aze43fb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aze43fb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-11-fill" {...props}></Icon>
