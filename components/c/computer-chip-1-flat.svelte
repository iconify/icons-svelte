<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lh0nbxbbj.css';
import '../../css/o/oj782tibt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lh0nbxbbj"/><path clip-rule="evenodd" class="oj782tibt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:computer-chip-1-flat" {...props}></Icon>
