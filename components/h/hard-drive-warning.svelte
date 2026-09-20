<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pchupzqhj.css';
import '../../css/h/hg71ebcsy.css';
import '../../css/c/c5skm7bip.css';
import '../../css/j/jeup4er5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pchupzqhj"/><path class="hg71ebcsy"/><path class="c5skm7bip"/><path class="jeup4er5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:hard-drive-warning" {...props}></Icon>
