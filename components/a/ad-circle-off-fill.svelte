<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lixmf10tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lixmf10tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ad-circle-off-fill" {...props}></Icon>
