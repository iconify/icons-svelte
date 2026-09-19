<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puatqp2zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="puatqp2zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:direction-right-down" {...props}></Icon>
