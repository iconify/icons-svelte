<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_ha40bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_ha40bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:floppy-disk-1-bold" {...props}></Icon>
