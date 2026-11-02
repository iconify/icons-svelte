<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soa9m9aph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="soa9m9aph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ampersands-line" {...props}></Icon>
