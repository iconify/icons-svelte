<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh26h9acs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh26h9acs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-clock-solid" {...props}></Icon>
