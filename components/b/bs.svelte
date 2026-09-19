<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sam6cytxx.css';
import '../../css/u/ubwiz66zy.css';
import '../../css/w/wiacdbgyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sam6cytxx"/><path class="ubwiz66zy"/><path class="wiacdbgyj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:bs" {...props}></Icon>
