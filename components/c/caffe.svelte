<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llog1wgkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":469,"height":512};
const content = `<path class="llog1wgkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:caffe" {...props}></Icon>
