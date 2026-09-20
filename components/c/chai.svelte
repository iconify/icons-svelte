<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkd4cobqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkd4cobqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:chai" {...props}></Icon>
