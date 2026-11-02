<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux3fr-b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux3fr-b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:building-4-fill" {...props}></Icon>
