<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/x---asbnp.css';
import '../../css/k/krrnwbcaq.css';
import '../../css/h/hxtv6eb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="x---asbnp"/><path class="krrnwbcaq"/><path class="hxtv6eb4e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:color-brush-2" {...props}></Icon>
