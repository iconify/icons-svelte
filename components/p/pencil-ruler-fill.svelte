<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iabzukq5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iabzukq5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-ruler-fill" {...props}></Icon>
