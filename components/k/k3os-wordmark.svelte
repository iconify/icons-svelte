<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8yruddxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u8yruddxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:k3os-wordmark" {...props}></Icon>
