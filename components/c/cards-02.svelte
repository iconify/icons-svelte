<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/ez3g9wb-c.css';
import '../../css/u/u5m8n7-ni.css';
import '../../css/s/sf-e43b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ez3g9wb-c"/><path class="u5m8n7-ni"/><path class="sf-e43b5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cards-02" {...props}></Icon>
