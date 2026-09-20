<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s04r6fc4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s04r6fc4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:goggles-fill" {...props}></Icon>
