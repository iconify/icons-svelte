<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahv5oyb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ahv5oyb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:candle-solid" {...props}></Icon>
