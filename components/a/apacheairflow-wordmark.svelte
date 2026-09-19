<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu9x3g38j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nu9x3g38j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:apacheairflow-wordmark" {...props}></Icon>
