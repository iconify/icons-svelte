<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhx61zfib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fhx61zfib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:chevron-right-compact" {...props}></Icon>
