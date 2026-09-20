<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/ilef90r2i.css';
import '../../css/g/gp2un2bwc.css';
import '../../css/m/m6eplnbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ilef90r2i"/><path class="gp2un2bwc"/><path class="m6eplnbnj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:keyboard-flat" {...props}></Icon>
