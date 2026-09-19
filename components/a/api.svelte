<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7sr6ubzr.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/h/h9y_epsde.css';
import '../../css/a/a--w-x__b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7sr6ubzr"/><g class="d2kvgvbvc"><path class="h9y_epsde"/><path class="a--w-x__b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:api" {...props}></Icon>
