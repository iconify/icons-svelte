<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/t/t08n0l47p.css';
import '../../css/m/mp4y6wb4i.css';
import '../../css/z/zodgzu85w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="t08n0l47p"/><path class="mp4y6wb4i"/><path class="zodgzu85w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:crypto-mining" {...props}></Icon>
