<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdjcw3-gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdjcw3-gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mirror" {...props}></Icon>
