<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_2j2gw1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_2j2gw1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-nigeria-line" {...props}></Icon>
