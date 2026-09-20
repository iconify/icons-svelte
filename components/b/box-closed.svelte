<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc-uk6b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="wc-uk6b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:box-closed" {...props}></Icon>
