<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_c4e9r8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_c4e9r8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:barrel-2-line" {...props}></Icon>
