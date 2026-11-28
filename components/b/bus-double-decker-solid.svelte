<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orr3tv0kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orr3tv0kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bus-double-decker-solid" {...props}></Icon>
