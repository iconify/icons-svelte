<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz3hkdpne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz3hkdpne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:cbs" {...props}></Icon>
