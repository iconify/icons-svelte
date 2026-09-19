<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqt6cf4sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="framer-logo-outline"><path class="(Stroke) Vector fqt6cf4sl" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:framer-logo-outline" {...props}></Icon>
