<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp9s_mb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="pp9s_mb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:fish" {...props}></Icon>
