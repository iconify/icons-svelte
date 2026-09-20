<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk1ggacie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="mk1ggacie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:basketball-11" {...props}></Icon>
