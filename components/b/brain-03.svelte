<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq9543b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq9543b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:brain-03" {...props}></Icon>
