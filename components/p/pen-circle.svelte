<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0ac8zb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q0ac8zb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pen-circle" {...props}></Icon>
