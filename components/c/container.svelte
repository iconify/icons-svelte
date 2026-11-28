<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tna_dgorv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tna_dgorv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:container" {...props}></Icon>
