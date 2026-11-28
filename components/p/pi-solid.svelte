<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db2kxhb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="db2kxhb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pi-solid" {...props}></Icon>
