<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m37gkopse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m37gkopse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:components-line" {...props}></Icon>
