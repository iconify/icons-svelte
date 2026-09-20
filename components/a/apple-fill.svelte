<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l34h5cbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l34h5cbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:apple-fill" {...props}></Icon>
