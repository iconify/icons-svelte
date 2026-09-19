<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhcvz-r0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhcvz-r0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-down-2-bold" {...props}></Icon>
