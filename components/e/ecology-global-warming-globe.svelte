<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fftuk_bwd.css';
import '../../css/a/ascdhq43i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fftuk_bwd"/><path class="ascdhq43i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:ecology-global-warming-globe" {...props}></Icon>
