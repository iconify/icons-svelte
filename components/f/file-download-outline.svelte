<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg1t_dv8x.css';
import '../../css/c/cgf21cybt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pg1t_dv8x"/><path clip-rule="evenodd" class="cgf21cybt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:file-download-outline" {...props}></Icon>
