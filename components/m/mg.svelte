<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/en_xgrb1u.css';
import '../../css/f/fns7ilq0e.css';
import '../../css/v/vabrm_bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="en_xgrb1u"/><path class="fns7ilq0e"/><path class="vabrm_bjl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:mg" {...props}></Icon>
