<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aopgjf_lo.css';
import '../../css/f/f-1ndobgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aopgjf_lo"/><path class="f-1ndobgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:note-20-bold" {...props}></Icon>
