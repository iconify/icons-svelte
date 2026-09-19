<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz-_z_9sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pz-_z_9sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:microsoftsqlserver-wordmark" {...props}></Icon>
