<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-ni3xu8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-ni3xu8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:panel-glass-door-4-locked" {...props}></Icon>
