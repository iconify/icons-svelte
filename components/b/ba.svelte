<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/l-nvvtu9k.css';
import '../../css/c/cj9i99glq.css';
import '../../css/z/z1k0_nbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="l-nvvtu9k"/><path class="cj9i99glq"/><path class="z1k0_nbcc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:ba" {...props}></Icon>
