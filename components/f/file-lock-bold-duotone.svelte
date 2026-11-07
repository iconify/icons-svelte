<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj6gwrmjs.css';
import '../../css/m/me55noe0w.css';
import '../../css/w/wz597j78j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj6gwrmjs"/><path clip-rule="evenodd" class="me55noe0w"/><path class="wz597j78j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-lock-bold-duotone" {...props}></Icon>
