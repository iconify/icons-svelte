<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg74q_5-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg74q_5-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:replace" {...props}></Icon>
