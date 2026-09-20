<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilt_3uyjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilt_3uyjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rose-fill" {...props}></Icon>
