<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6tzh5bbz.css';
import '../../css/x/xkrbx0bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a6tzh5bbz"/><path class="xkrbx0bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:display-bold-duotone" {...props}></Icon>
