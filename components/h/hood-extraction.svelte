<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn9pt63aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn9pt63aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hood-extraction" {...props}></Icon>
