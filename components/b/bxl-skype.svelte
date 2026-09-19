<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0sdzubwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0sdzubwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-skype" {...props}></Icon>
