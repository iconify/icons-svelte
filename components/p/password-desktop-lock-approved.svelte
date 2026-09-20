<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xl07tt-6b.css';
import '../../css/f/fmam1lxxs.css';
import '../../css/c/ct1flbcol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xl07tt-6b"/><path class="fmam1lxxs"/><path class="ct1flbcol"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:password-desktop-lock-approved" {...props}></Icon>
