<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/z58p1d3ec.css';
import '../../css/t/tscluyl0b.css';
import '../../css/u/uwqzc_bsf.css';
import '../../css/v/vis7tzbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="z58p1d3ec"/><path class="tscluyl0b"/><path class="uwqzc_bsf"/><path class="vis7tzbty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:database-network-1" {...props}></Icon>
