<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2dw2dclf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p2dw2dclf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:globe-24px" {...props}></Icon>
