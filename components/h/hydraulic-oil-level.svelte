<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avq65hbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avq65hbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hydraulic-oil-level" {...props}></Icon>
