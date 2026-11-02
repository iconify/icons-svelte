<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3o0hc51j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3o0hc51j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bed-fill" {...props}></Icon>
