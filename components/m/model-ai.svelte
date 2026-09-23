<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-ot-hb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-ot-hb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:model-ai" {...props}></Icon>
