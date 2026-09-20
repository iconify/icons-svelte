<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj96fvbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj96fvbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:left-fill" {...props}></Icon>
