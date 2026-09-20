<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqv-6tbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kqv-6tbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:deepfake-technology-1" {...props}></Icon>
