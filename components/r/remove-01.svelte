<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh_7twlpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh_7twlpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:remove-01" {...props}></Icon>
