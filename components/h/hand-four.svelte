<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd2xhk3go.css';
import '../../css/o/oaj_2iwov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dd2xhk3go"/><path class="oaj_2iwov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:hand-four" {...props}></Icon>
