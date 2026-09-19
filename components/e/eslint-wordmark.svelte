<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2lb21bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u2lb21bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:eslint-wordmark" {...props}></Icon>
