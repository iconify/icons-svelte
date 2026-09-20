<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dal7ae8el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dal7ae8el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flash-fill" {...props}></Icon>
