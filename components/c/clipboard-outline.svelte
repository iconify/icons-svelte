<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/m7n6j24vy.css';
import '../../css/m/m4i8f4b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="clipboard-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="m7n6j24vy"/><path class="m4i8f4b0e"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:clipboard-outline" {...props}></Icon>
