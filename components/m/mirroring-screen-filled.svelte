<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nac6i9phy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nac6i9phy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mirroring-screen-filled" {...props}></Icon>
