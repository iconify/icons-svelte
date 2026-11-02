<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6xiabc5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6xiabc5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rest-area-line" {...props}></Icon>
