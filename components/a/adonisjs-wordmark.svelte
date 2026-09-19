<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0efq_bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="m0efq_bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:adonisjs-wordmark" {...props}></Icon>
