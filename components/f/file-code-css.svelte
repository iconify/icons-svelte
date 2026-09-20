<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/v/v173lkz4p.css';
import '../../css/n/na_4mhdsu.css';
import '../../css/u/ung0jz3kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="v173lkz4p"/><path class="na_4mhdsu"/><path class="ung0jz3kx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:file-code-css" {...props}></Icon>
