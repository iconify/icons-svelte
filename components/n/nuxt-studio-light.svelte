<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ano3tzyta.css';
import '../../css/t/tey8c23jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":227,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ano3tzyta"/><path class="tey8c23jn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nuxt-studio-light" {...props}></Icon>
