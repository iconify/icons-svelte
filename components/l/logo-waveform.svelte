<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndzk00itk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ndzk00itk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:logo-waveform" {...props}></Icon>
