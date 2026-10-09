<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flkoy18ai.css';
import '../../css/h/h0fs14upu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="flkoy18ai"/><path class="h0fs14upu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:burger-48" {...props}></Icon>
