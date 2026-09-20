<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbhvncbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sbhvncbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:kaldi" {...props}></Icon>
