<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx7t24bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx7t24bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dartboard" {...props}></Icon>
