<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/uoqau0b3r.css';
import '../../css/p/pu5v9vwih.css';
import '../../css/p/pmz80t_au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="uoqau0b3r"/><path class="pu5v9vwih"/><path class="pmz80t_au"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:mq" {...props}></Icon>
