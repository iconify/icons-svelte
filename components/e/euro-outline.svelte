<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iesh8dbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iesh8dbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:euro-outline" {...props}></Icon>
