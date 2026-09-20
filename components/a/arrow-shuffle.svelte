<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-vm_3b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-vm_3b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-shuffle" {...props}></Icon>
