<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0n8thbpp.css';
import '../../css/a/azwi-ublj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q0n8thbpp"/><path class="azwi-ublj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:opensuse" {...props}></Icon>
