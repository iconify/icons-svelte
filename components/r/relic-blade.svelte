<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axk8kbb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="axk8kbb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:relic-blade" {...props}></Icon>
