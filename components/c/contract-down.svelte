<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtugqvbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtugqvbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:contract-down" {...props}></Icon>
