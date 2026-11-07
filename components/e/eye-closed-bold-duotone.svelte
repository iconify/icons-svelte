<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxw0gio2t.css';
import '../../css/k/k8vhtfbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dxw0gio2t"/><path class="k8vhtfbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:eye-closed-bold-duotone" {...props}></Icon>
