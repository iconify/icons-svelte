<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7hkk8ylo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="s7hkk8ylo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:realm-wordmark" {...props}></Icon>
