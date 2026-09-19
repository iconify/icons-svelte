<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0n74mbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l0n74mbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:corejs-wordmark" {...props}></Icon>
