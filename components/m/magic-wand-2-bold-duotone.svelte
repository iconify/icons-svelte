<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxk_x0b5m.css';
import '../../css/o/o1oqmebja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxk_x0b5m"/><path class="o1oqmebja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magic-wand-2-bold-duotone" {...props}></Icon>
