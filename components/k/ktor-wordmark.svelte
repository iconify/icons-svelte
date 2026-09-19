<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asr9__sng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="asr9__sng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:ktor-wordmark" {...props}></Icon>
