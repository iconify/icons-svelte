<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjlxljkka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjlxljkka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-arrow-down-outline" {...props}></Icon>
