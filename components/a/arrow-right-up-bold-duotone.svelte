<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp8cnibtf.css';
import '../../css/g/g95h_vbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mp8cnibtf"/><path class="g95h_vbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-up-bold-duotone" {...props}></Icon>
