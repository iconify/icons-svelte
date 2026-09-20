<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfd28zbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfd28zbhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bus-alt" {...props}></Icon>
