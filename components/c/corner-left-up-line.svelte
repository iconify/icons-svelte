<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3wzldugj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3wzldugj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:corner-left-up-line" {...props}></Icon>
