<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmkku_bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmkku_bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eyeglass-line" {...props}></Icon>
