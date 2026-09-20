<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bxu-ixbxe.css';
import '../../css/v/v8vm-z-vm.css';
import '../../css/x/xwni9mcbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bxu-ixbxe"/><path class="v8vm-z-vm"/><circle class="xwni9mcbw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:bell-dot" {...props}></Icon>
