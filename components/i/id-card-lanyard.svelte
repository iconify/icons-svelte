<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/f2yqqib5f.css';
import '../../css/x/xvdfgms8f.css';
import '../../css/i/ide5axbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f2yqqib5f"/><path class="xvdfgms8f"/><circle class="ide5axbrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:id-card-lanyard" {...props}></Icon>
