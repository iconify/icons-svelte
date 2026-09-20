<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/u5wmu6hoi.css';
import '../../css/n/nwr2oub_h.css';
import '../../css/a/av0kmmbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u5wmu6hoi"/><path class="nwr2oub_h"/><circle class="av0kmmbuk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:file-search-corner" {...props}></Icon>
