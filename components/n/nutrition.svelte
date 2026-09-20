<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh6xk1tzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh6xk1tzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:nutrition" {...props}></Icon>
