<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tauuimkqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tauuimkqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comma-circle-outline" {...props}></Icon>
