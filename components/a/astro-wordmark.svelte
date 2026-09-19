<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0z8i7m6l.css';
import '../../css/t/tr2lgt9jh.css';
import '../../css/y/y8s2o56ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="o0z8i7m6l"/><path class="tr2lgt9jh"/><path class="y8s2o56ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:astro-wordmark" {...props}></Icon>
