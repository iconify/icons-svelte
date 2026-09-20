<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/vybouiput.css';
import '../../css/k/kt8n5eewz.css';
import '../../css/o/o50ddxiay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vybouiput"/><path class="kt8n5eewz"/><circle class="o50ddxiay"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:file-music" {...props}></Icon>
