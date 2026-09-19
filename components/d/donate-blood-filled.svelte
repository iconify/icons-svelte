<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urr2ffbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urr2ffbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:donate-blood-filled" {...props}></Icon>
