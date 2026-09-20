<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nngrh28lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nngrh28lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fast-forward-10" {...props}></Icon>
