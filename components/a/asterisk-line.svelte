<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijx_gn60x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijx_gn60x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:asterisk-line" {...props}></Icon>
