<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1ndrfb_z.css';
import '../../css/x/x4f46-b2l.css';
import '../../css/a/ayfii2kus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1ndrfb_z"/><path class="x4f46-b2l"/><path class="ayfii2kus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-corrupted-bold-duotone" {...props}></Icon>
