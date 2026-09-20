<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luy5b2qht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="luy5b2qht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gate-and" {...props}></Icon>
