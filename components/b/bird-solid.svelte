<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scrkslm_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scrkslm_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bird-solid" {...props}></Icon>
