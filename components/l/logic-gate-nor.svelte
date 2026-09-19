<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an4mqobkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="an4mqobkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:logic-gate-nor" {...props}></Icon>
