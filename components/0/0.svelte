<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smb428ckv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="smb428ckv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:0" {...props}></Icon>
