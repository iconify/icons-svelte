<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/m7n6j24vy.css';
import '../../css/e/e2kb8cc5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="clipboard-text-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="m7n6j24vy"/><path class="e2kb8cc5n"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:clipboard-text-outline" {...props}></Icon>
