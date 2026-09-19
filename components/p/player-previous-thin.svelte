<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_3_bibbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_3_bibbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-previous-thin" {...props}></Icon>
