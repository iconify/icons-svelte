<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmycjebkn.css';
import '../../css/f/f6krj6bdn.css';
import '../../css/i/i6na-zfmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hmycjebkn"/><path class="f6krj6bdn"/><path class="i6na-zfmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-z-environments-dev-sec-ops" {...props}></Icon>
