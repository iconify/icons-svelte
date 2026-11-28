<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd68rr0ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd68rr0ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-three-quarter-solid" {...props}></Icon>
