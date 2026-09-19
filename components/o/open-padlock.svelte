<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwlarub2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="gwlarub2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:open-padlock" {...props}></Icon>
