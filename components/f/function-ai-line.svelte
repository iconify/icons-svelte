<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhc-xmblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhc-xmblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:function-ai-line" {...props}></Icon>
