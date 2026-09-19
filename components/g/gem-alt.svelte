<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9xf8n8nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9xf8n8nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gem-alt" {...props}></Icon>
