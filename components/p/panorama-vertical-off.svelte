<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwryu69jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwryu69jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:panorama-vertical-off" {...props}></Icon>
