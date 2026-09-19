<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb95o6e0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb95o6e0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:computer-desk-01" {...props}></Icon>
