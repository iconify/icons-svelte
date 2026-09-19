<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj9jg98vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mj9jg98vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:ecg" {...props}></Icon>
