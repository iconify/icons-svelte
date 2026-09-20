<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svv659cxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svv659cxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rocket-linear" {...props}></Icon>
