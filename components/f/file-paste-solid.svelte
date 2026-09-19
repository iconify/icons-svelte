<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/wm9scpbjq.css';
import '../../css/i/i30we8_-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="wm9scpbjq"/><path class="i30we8_-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-paste-solid" {...props}></Icon>
