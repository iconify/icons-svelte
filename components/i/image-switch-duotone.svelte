<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcti67wgz.css';
import '../../css/v/votvkdbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcti67wgz"/><path class="votvkdbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-switch-duotone" {...props}></Icon>
