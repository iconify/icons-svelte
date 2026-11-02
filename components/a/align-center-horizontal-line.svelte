<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmtwrx6vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmtwrx6vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-center-horizontal-line" {...props}></Icon>
