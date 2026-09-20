<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plg1gtjuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plg1gtjuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cactus-fill" {...props}></Icon>
