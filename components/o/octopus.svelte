<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/akttfdcoa.css';
import '../../css/a/atmw7hb7t.css';
import '../../css/h/h1wcxz_fz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="akttfdcoa"/><path class="atmw7hb7t"/><path class="h1wcxz_fz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:octopus" {...props}></Icon>
