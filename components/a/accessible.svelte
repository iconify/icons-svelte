<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw9hj7r8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw9hj7r8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:accessible" {...props}></Icon>
