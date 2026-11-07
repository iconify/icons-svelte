<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj6gwrmjs.css';
import '../../css/q/q4s8ed2cu.css';
import '../../css/x/x4f46-b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj6gwrmjs"/><path class="q4s8ed2cu"/><path class="x4f46-b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-image-bold-duotone" {...props}></Icon>
