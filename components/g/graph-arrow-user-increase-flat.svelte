<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/neb-6ibuu.css';
import '../../css/a/aztfelb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="neb-6ibuu"/><path clip-rule="evenodd" class="aztfelb7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:graph-arrow-user-increase-flat" {...props}></Icon>
