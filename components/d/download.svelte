<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtw3e_bsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtw3e_bsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:download" {...props}></Icon>
