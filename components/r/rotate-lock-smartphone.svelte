<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qlodfi8rw.css';
import '../../css/x/x35k9g5le.css';
import '../../css/t/t044i1_sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qlodfi8rw"/><path class="x35k9g5le"/><path class="t044i1_sg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:rotate-lock-smartphone" {...props}></Icon>
