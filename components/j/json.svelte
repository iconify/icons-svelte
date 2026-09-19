<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jykbmnblb.css';
import '../../css/k/kpcu7cc2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jykbmnblb"/><path clip-rule="evenodd" class="kpcu7cc2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:json" {...props}></Icon>
