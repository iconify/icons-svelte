<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhaym9b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhaym9b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mountain-2-fill" {...props}></Icon>
