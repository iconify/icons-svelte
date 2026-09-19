<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/o/oae8n8nad.css';
import '../../css/q/q78tzvb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="lock-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="oae8n8nad"/><path class="q78tzvb-n"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:lock-outline" {...props}></Icon>
