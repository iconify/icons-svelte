<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz9ohguhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz9ohguhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dexe" {...props}></Icon>
