<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myj5jg_sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myj5jg_sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:aspect-ratio-round" {...props}></Icon>
