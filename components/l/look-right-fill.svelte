<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcghp2bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xcghp2bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:look-right-fill" {...props}></Icon>
