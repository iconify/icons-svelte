<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8czseb2v.css';
import '../../css/e/e_ax9fbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8czseb2v"/><path class="e_ax9fbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bell-bold-duotone" {...props}></Icon>
