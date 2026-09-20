<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfotv0bxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfotv0bxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-horiz-center-detailed-line" {...props}></Icon>
