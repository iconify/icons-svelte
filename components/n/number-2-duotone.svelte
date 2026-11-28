<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcxaaqz_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcxaaqz_m primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-2-duotone" {...props}></Icon>
