<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/te-6n-baq.css';
import '../../css/e/eh8r4ccab.css';
import '../../css/e/e2cr6acpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="te-6n-baq"/><path class="eh8r4ccab"/><path class="e2cr6acpy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:calculator" {...props}></Icon>
