<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzpfhccmd.css';
import '../../css/y/yg46shszw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tzpfhccmd"/><path class="yg46shszw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cursor-bold-duotone" {...props}></Icon>
