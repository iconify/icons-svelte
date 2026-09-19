<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih55uac0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih55uac0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-factory" {...props}></Icon>
