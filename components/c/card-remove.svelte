<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu6f67tyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uu6f67tyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-remove" {...props}></Icon>
