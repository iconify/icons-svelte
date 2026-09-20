<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_sdbxlje.css';
import '../../css/r/rs1l3rb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_sdbxlje"/><path class="rs1l3rb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bscpad" {...props}></Icon>
