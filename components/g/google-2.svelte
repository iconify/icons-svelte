<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s769v6bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s769v6bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:google-2" {...props}></Icon>
