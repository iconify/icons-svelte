<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df4em2bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="df4em2bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:radio-bulk-round" {...props}></Icon>
