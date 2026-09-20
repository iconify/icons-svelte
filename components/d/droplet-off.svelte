<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al3ffg0_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al3ffg0_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:droplet-off" {...props}></Icon>
