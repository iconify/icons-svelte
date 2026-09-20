<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmapptb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmapptb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:glasses-fill" {...props}></Icon>
