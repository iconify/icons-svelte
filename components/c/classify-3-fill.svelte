<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usus0y30x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="usus0y30x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-3-fill" {...props}></Icon>
