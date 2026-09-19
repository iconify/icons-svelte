<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg2_2cs5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pg2_2cs5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:alarm-smoke" {...props}></Icon>
