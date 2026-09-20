<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz3d-2pmb.css';
import '../../css/s/spm3uswvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rz3d-2pmb"/><path class="spm3uswvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:edit" {...props}></Icon>
