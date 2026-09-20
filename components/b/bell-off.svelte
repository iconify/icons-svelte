<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akkca56wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akkca56wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:bell-off" {...props}></Icon>
