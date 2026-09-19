<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dgeqk47rg.css';
import '../../css/i/iyn9fmbzw.css';
import '../../css/x/xkg6e8cwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dgeqk47rg"/><path class="iyn9fmbzw"/><path class="xkg6e8cwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:lv" {...props}></Icon>
