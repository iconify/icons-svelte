<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpfw86bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpfw86bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-euro-fill" {...props}></Icon>
