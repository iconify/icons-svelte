<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk944wb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk944wb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:document-2-line" {...props}></Icon>
