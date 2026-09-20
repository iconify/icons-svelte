<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmu9f6bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmu9f6bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:air-conditioning" {...props}></Icon>
