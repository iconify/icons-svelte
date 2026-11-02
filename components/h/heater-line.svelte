<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d30yuabfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d30yuabfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heater-line" {...props}></Icon>
