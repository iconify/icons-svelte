<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz1r5ijls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mz1r5ijls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:paw-off" {...props}></Icon>
