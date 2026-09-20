<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrg32xrff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jrg32xrff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:radioactive-2-solid" {...props}></Icon>
