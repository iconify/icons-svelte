<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-nqt_bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="u-nqt_bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-power-1" {...props}></Icon>
