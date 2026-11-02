<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvnosdbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvnosdbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moai-fill" {...props}></Icon>
